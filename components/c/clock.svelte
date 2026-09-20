<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaye1ubvf.css';
import '../../css/e/ej6vge06z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uaye1ubvf"/><path class="ej6vge06z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:clock" {...props}></Icon>
