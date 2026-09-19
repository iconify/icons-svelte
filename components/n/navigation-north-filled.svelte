<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx4xbjb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx4xbjb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:navigation-north-filled" {...props}></Icon>
