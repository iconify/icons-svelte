<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr3-7w_6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3-7w_6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-left-large-fill-round" {...props}></Icon>
