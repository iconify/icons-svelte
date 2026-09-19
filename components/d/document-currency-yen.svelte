<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imh9d0bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imh9d0bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-yen" {...props}></Icon>
