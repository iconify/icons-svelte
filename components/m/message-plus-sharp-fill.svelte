<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdghcp3-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdghcp3-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-plus-sharp-fill" {...props}></Icon>
