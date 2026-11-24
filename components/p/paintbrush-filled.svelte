<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrs61fdze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrs61fdze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paintbrush-filled" {...props}></Icon>
