<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqgrzwrtu.css';
import '../../css/j/jahmehbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eqgrzwrtu"/><path class="jahmehbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-box-down-20" {...props}></Icon>
