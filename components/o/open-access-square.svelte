<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu1_c1gnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bu1_c1gnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:open-access-square" {...props}></Icon>
