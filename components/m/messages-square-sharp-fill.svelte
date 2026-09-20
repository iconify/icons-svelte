<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix1u1i3gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix1u1i3gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages-square-sharp-fill" {...props}></Icon>
