<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eak-paccj.css';
import '../../css/h/hiszw8brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eak-paccj"/><path class="hiszw8brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-x-filled" {...props}></Icon>
