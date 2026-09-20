<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhxqgv93k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhxqgv93k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-question" {...props}></Icon>
