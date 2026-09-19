<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlkfmlbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlkfmlbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flag-alt-filled" {...props}></Icon>
