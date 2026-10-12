<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pehpq5qtd.css';
import '../../css/b/ba28ldwhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pehpq5qtd"/><path class="ba28ldwhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-minus-filled" {...props}></Icon>
