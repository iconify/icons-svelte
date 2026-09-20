<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnx0k3uqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnx0k3uqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-cancel" {...props}></Icon>
