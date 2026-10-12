<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u90t3vbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u90t3vbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calculator-filled" {...props}></Icon>
