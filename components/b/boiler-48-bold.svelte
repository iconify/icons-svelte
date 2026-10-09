<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zanasbbem.css';
import '../../css/i/iqca1hbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zanasbbem"/><path class="iqca1hbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-48-bold" {...props}></Icon>
