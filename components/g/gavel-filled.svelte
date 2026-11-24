<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmb5cnbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmb5cnbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gavel-filled" {...props}></Icon>
