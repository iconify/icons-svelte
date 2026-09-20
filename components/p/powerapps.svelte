<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ctcbc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ctcbc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:powerapps" {...props}></Icon>
