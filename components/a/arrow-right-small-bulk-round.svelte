<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alvyp9n1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alvyp9n1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-small-bulk-round" {...props}></Icon>
