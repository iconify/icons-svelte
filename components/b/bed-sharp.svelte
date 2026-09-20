<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd99nnc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd99nnc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-sharp" {...props}></Icon>
