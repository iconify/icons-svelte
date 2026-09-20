<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjekp7b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjekp7b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-smile-plus-sharp" {...props}></Icon>
