<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up4gwh-bs.css';
import '../../css/u/uv693bcmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up4gwh-bs"/><path class="uv693bcmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:battery-bolt" {...props}></Icon>
