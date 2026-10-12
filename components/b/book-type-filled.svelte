<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj8zh9bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wj8zh9bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-type-filled" {...props}></Icon>
