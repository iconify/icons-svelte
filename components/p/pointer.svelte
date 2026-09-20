<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqf_bmbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gqf_bmbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pointer" {...props}></Icon>
