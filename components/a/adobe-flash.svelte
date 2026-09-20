<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6hno2bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k6hno2bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:adobe-flash" {...props}></Icon>
