<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl5kxt80y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl5kxt80y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:at" {...props}></Icon>
