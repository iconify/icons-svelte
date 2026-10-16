<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yybeh6b4o.css';
import '../../css/r/rc1rp4d6j.css';
import '../../css/h/h2w2gxl4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yybeh6b4o"/><path class="rc1rp4d6j"/><path class="h2w2gxl4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gravity-base-48-bold" {...props}></Icon>
