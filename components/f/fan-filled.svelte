<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh5rds2bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fh5rds2bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fan-filled" {...props}></Icon>
