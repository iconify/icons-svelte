<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v65-pnbdf.css';
import '../../css/x/x7p3n33kb.css';
import '../../css/w/woyhp54cm.css';
import '../../css/q/qwc3a0irv.css';
import '../../css/f/fu441_fbu.css';
import '../../css/d/d6o62kkbs.css';
import '../../css/o/o4ydui5gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v65-pnbdf"/><path class="x7p3n33kb"/><path class="woyhp54cm"/><path class="qwc3a0irv"/><path class="fu441_fbu"/><path class="d6o62kkbs"/><path class="o4ydui5gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-barcode" {...props}></Icon>
