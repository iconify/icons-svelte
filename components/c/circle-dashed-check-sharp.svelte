<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ho668zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ho668zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-dashed-check-sharp" {...props}></Icon>
