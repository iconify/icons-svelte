<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9j7jcc_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9j7jcc_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:building-alt-03-filled" {...props}></Icon>
