<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgpc9ugqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgpc9ugqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:border-bottom" {...props}></Icon>
