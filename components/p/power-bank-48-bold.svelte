<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5qj0td2j.css';
import '../../css/v/vyrx1cnfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h5qj0td2j"/><path class="vyrx1cnfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-bank-48-bold" {...props}></Icon>
