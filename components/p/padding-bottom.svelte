<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8k9kjbqe.css';
import '../../css/u/u_90zur1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t8k9kjbqe"/><path class="u_90zur1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:padding-bottom" {...props}></Icon>
