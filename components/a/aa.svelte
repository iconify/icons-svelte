<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm1099b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1099b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aa" {...props}></Icon>
