<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcufrbbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcufrbbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hourglass-line-bold" {...props}></Icon>
