<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6-rj3xvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-rj3xvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:error" {...props}></Icon>
