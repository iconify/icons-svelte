<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/e9waokbhr.css';
import '../../css/g/g7z2j-78e.css';
import '../../css/q/q7do0tepr.css';
import '../../css/c/c1t--rtgz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGT468QRJI"><g class="v3_i3wktz"><path class="e9waokbhr"/><path class="g7z2j-78e"/><path class="q7do0tepr"/><path class="c1t--rtgz"/></g></mask></defs><path mask="url(#SVGT468QRJI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:joystick" {...props}></Icon>
