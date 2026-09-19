<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6t4d8u5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n6t4d8u5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:filter-small" {...props}></Icon>
