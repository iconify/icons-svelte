<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqpbul-cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqpbul-cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:comic-bubble" {...props}></Icon>
