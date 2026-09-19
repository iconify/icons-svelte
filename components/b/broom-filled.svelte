<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2fvsfbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2fvsfbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:broom-filled" {...props}></Icon>
