<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_a0-8m9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_a0-8m9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:inventory-line" {...props}></Icon>
