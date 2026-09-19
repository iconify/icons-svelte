<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk94esn1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk94esn1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-square" {...props}></Icon>
