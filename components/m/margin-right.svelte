<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3glxibdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n3glxibdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:margin-right" {...props}></Icon>
