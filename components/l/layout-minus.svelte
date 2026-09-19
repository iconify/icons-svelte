<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxvivyn1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b yxvivyn1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layout-minus" {...props}></Icon>
