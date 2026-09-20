<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9xaj9h1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9xaj9h1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hierarchy-2" {...props}></Icon>
