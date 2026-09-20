<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acwekrqsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="acwekrqsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:list" {...props}></Icon>
