<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzqwh5b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqwh5b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:minus-square-filled" {...props}></Icon>
