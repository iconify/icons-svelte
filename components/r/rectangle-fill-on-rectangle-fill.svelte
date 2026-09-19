<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zml9i3ljd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zml9i3ljd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-fill-on-rectangle-fill" {...props}></Icon>
