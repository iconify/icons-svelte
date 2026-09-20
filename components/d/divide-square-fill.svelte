<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8m2hz8lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8m2hz8lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:divide-square-fill" {...props}></Icon>
