<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec1x-acku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1x-acku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-minus" {...props}></Icon>
