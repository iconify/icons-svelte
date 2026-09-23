<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as0oiybee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as0oiybee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-down-right-sharp-fill" {...props}></Icon>
