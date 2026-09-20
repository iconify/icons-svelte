<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdd_2cbom.css';
import '../../css/e/e-z6fbc7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pdd_2cbom"/><path class="e-z6fbc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:book-percent" {...props}></Icon>
