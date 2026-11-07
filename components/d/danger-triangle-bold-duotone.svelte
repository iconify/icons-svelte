<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkvl0ybhw.css';
import '../../css/q/qosnnxx8l.css';
import '../../css/x/x41xvfi0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkvl0ybhw"/><path class="qosnnxx8l"/><path class="x41xvfi0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-triangle-bold-duotone" {...props}></Icon>
