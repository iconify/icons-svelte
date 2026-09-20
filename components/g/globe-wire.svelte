<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4yq3qb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e4yq3qb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:globe-wire" {...props}></Icon>
