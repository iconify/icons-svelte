<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2nt36b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2nt36b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:planet" {...props}></Icon>
