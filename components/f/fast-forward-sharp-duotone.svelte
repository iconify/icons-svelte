<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc2r4ounr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc2r4ounr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fast-forward-sharp-duotone" {...props}></Icon>
