<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg2ap3bxj.css';
import '../../css/l/l5-kz1soe.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gg2ap3bxj"/><path class="l5-kz1soe"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-alert-48" {...props}></Icon>
