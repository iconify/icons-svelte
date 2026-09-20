<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/x/xcv6q1bnv.css';
import '../../css/o/oba9rfsja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><circle class="xcv6q1bnv"/><path class="oba9rfsja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-add-circle-button-remove-cross-add-buttons-plus-circle" {...props}></Icon>
