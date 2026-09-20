<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9-vddblh.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av3m8fbrw.css';
import '../../css/e/eerv4xbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG67GspdNb" class="p9-vddblh"/></defs><g class="ft5dv1b6b"><use href="#SVG67GspdNb"/><use href="#SVG67GspdNb" class="av3m8fbrw"/><path class="eerv4xbeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-divider-horizontal" {...props}></Icon>
