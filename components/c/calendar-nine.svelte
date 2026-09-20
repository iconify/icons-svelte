<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aey68mb3i.css';
import '../../css/y/ynooprbfx.css';
import '../../css/y/yc1hb9b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aey68mb3i"/><path class="ynooprbfx"/><path clip-rule="evenodd" class="yc1hb9b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-nine" {...props}></Icon>
