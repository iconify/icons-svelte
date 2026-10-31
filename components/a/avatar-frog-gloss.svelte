<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4-1rtbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4-1rtbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-frog-gloss" {...props}></Icon>
