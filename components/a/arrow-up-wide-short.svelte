<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_2qg0fkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="j_2qg0fkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-up-wide-short" {...props}></Icon>
