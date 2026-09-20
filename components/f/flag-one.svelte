<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enq9vkb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enq9vkb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:flag-one" {...props}></Icon>
