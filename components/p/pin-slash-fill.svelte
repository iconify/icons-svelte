<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5wjhcbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="e5wjhcbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pin-slash-fill" {...props}></Icon>
