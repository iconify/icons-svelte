<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4w-kt03b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4w-kt03b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-cog" {...props}></Icon>
