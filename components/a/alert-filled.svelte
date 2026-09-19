<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlv8u-u-t.css';
import '../../css/a/aso8_oe6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="xlv8u-u-t"/><path class="aso8_oe6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:alert-filled" {...props}></Icon>
