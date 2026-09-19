<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/k/kwtkd3b7k.css';
import '../../css/r/r9r4dibst.css';
import '../../css/x/xprwyhbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="kwtkd3b7k"/><circle class="r9r4dibst"/><circle class="xprwyhbwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:options" {...props}></Icon>
