<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7w121h3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7w121h3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency" {...props}></Icon>
