<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovkd8pb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ovkd8pb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:exclamation-circle" {...props}></Icon>
