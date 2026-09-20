<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm1d98grv.css';
import '../../css/r/rgiy7zbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lm1d98grv"/><path class="rgiy7zbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flip-v" {...props}></Icon>
