<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1rlpabge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1rlpabge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dungeonsanddragons" {...props}></Icon>
