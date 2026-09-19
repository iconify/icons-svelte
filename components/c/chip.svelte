<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9lfmybtd.css';
import '../../css/y/yeioovmxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9lfmybtd"/><path class="yeioovmxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chip" {...props}></Icon>
