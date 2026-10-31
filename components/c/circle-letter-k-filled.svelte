<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ruxowru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7ruxowru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-k-filled" {...props}></Icon>
