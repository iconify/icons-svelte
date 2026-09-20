<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4721q_ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path paint-order="fill markers stroke" class="o4721q_ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:quokka" {...props}></Icon>
