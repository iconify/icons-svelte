<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6sjyt58t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t6sjyt58t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-indian-rupee-filled" {...props}></Icon>
