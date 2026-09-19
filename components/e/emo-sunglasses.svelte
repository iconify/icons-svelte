<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnvj_8bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":990,"height":1000};
const content = `<path class="hnvj_8bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-sunglasses" {...props}></Icon>
