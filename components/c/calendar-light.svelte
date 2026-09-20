<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi5syqv6f.css';
import '../../css/y/ynooprbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi5syqv6f"/><path class="ynooprbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-light" {...props}></Icon>
