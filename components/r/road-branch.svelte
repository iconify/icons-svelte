<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y14v4mbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y14v4mbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:road-branch" {...props}></Icon>
