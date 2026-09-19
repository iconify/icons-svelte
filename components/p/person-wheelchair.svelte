<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imc_ozwsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="imc_ozwsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-wheelchair" {...props}></Icon>
