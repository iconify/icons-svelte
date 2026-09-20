<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2s5ybq2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2s5ybq2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layers-union" {...props}></Icon>
