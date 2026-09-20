<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nkj12ubkl.css';
import '../../css/f/fbnpwsodw.css';
import '../../css/x/xeitc2b3n.css';
import '../../css/y/yu2ef9i5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nkj12ubkl"/><circle class="fbnpwsodw"/><path class="xeitc2b3n"/><circle class="yu2ef9i5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image" {...props}></Icon>
