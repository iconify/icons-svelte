<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj-ptsmyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj-ptsmyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:color-fill" {...props}></Icon>
