<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8qh8v6xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8qh8v6xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:island" {...props}></Icon>
