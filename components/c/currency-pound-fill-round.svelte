<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_nbxrbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_nbxrbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-pound-fill-round" {...props}></Icon>
