<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5ohcpp2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ohcpp2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-filled" {...props}></Icon>
