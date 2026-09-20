<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl13osb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dl13osb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-menu-left" {...props}></Icon>
