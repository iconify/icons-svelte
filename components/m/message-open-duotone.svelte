<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnor7rbtu.css';
import '../../css/i/iim7l5brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnor7rbtu"/><path class="iim7l5brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:message-open-duotone" {...props}></Icon>
