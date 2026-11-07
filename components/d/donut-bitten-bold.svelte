<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4wd7-nbs.css';
import '../../css/j/jrqzroung.css';
import '../../css/x/xbekolb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4wd7-nbs"/><path class="jrqzroung"/><path clip-rule="evenodd" class="xbekolb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:donut-bitten-bold" {...props}></Icon>
