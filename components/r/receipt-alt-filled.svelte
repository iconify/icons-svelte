<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg69u6buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg69u6buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:receipt-alt-filled" {...props}></Icon>
