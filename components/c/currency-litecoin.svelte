<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3tqao7_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3tqao7_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-litecoin" {...props}></Icon>
