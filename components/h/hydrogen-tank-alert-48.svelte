<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifzu40bfd.css';
import '../../css/i/iyti-7bea.css';
import '../../css/h/hjhs5_6_n.css';
import '../../css/i/iqzpqgb0i.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ifzu40bfd"/><path class="iyti-7bea"/><path class="hjhs5_6_n"/><path class="iqzpqgb0i"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-tank-alert-48" {...props}></Icon>
