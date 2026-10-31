<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2rzysexz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2rzysexz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-w-filled" {...props}></Icon>
