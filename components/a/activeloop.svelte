<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja4g38bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja4g38bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:activeloop" {...props}></Icon>
