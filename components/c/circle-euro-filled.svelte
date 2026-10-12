<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-rcg7b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-rcg7b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-euro-filled" {...props}></Icon>
