<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfcm4db9i.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av3m8fbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG9V55xcZL" class="gfcm4db9i"/></defs><g class="ft5dv1b6b"><use href="#SVG9V55xcZL"/><use href="#SVG9V55xcZL" class="av3m8fbrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-windows" {...props}></Icon>
