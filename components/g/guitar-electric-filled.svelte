<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2gpqkf8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2gpqkf8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:guitar-electric-filled" {...props}></Icon>
