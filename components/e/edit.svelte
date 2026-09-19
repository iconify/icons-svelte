<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko_3_kw6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ko_3_kw6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:edit" {...props}></Icon>
