<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-bkmkdvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-bkmkdvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:number-sign" {...props}></Icon>
