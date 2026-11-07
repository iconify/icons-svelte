<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qosnnxx8l.css';
import '../../css/x/x41xvfi0c.css';
import '../../css/h/h0ezbvb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qosnnxx8l"/><path class="x41xvfi0c"/><path clip-rule="evenodd" class="h0ezbvb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-triangle-outline" {...props}></Icon>
