<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gosxrab6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gosxrab6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-minus-filled" {...props}></Icon>
