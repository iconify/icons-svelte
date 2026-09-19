<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqjjdx6vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hqjjdx6vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:billed-cap-small" {...props}></Icon>
