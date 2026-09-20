<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n42f4kkrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n42f4kkrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:leaf-two" {...props}></Icon>
