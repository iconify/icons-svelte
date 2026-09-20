<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti7rj0bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti7rj0bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:car-washing-line" {...props}></Icon>
