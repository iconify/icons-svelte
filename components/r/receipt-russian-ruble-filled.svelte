<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir0ltxjco.css';
import '../../css/c/c-llp8bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0ltxjco"/><path clip-rule="evenodd" class="c-llp8bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-russian-ruble-filled" {...props}></Icon>
