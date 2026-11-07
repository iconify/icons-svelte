<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhh-lmb1b.css';
import '../../css/w/wioqj5bua.css';
import '../../css/r/ru5wvccub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhh-lmb1b"/><path class="wioqj5bua"/><path clip-rule="evenodd" class="ru5wvccub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-square-3-outline" {...props}></Icon>
