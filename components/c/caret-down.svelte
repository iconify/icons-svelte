<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfto5fbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dfto5fbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:caret-down" {...props}></Icon>
