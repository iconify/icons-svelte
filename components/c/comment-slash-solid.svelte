<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pda7mmfqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pda7mmfqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:comment-slash-solid" {...props}></Icon>
