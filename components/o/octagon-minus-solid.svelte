<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqph13jba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqph13jba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-minus-solid" {...props}></Icon>
