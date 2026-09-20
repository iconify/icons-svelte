<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz2c4cb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz2c4cb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-riyal" {...props}></Icon>
