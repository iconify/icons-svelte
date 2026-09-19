<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d90m7rm_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d90m7rm_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-show-5-gen-2" {...props}></Icon>
