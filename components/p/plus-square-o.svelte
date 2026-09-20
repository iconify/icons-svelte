<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwz_oybvs.css';
import '../../css/c/cflr1ab0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uwz_oybvs"/><path class="cflr1ab0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:plus-square-o" {...props}></Icon>
