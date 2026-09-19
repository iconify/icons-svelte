<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvo1o4byr.css';
import '../../css/q/qzwrsetpw.css';
import '../../css/z/z8xma-crw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nvo1o4byr"/><path class="qzwrsetpw"/><path class="z8xma-crw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bactriancamel" {...props}></Icon>
