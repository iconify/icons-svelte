<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrnno4lpy.css';
import '../../css/q/qr4uhui_c.css';
import '../../css/f/fk2gskbbg.css';
import '../../css/v/v0e3hepfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jrnno4lpy"/><path class="qr4uhui_c"/><path class="fk2gskbbg"/><path class="v0e3hepfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chalet-48-bold" {...props}></Icon>
