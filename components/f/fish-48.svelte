<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohpbt_2nc.css';
import '../../css/h/h5dbk_bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ohpbt_2nc"/><path class="h5dbk_bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fish-48" {...props}></Icon>
