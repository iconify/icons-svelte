<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4nd5ibfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4nd5ibfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:expand-bulk-round" {...props}></Icon>
