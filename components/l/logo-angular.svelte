<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6ebachz.css';
import '../../css/z/zeqvi16vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vn6ebachz"/><path class="zeqvi16vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-angular" {...props}></Icon>
