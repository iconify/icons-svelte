<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae-x9bbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae-x9bbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flag-filled" {...props}></Icon>
