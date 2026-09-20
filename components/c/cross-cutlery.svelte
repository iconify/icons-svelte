<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4byx8bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t4byx8bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cross-cutlery" {...props}></Icon>
