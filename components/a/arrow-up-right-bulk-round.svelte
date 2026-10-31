<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izkg53yvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izkg53yvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-bulk-round" {...props}></Icon>
