<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r35m9-gnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r35m9-gnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:reorder-fill" {...props}></Icon>
