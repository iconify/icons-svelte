<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmlnfs7bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmlnfs7bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-japanese-yen" {...props}></Icon>
