<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av6p3g-os.css';
import '../../css/h/hdmntob4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av6p3g-os"/><path class="hdmntob4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:message-duotone" {...props}></Icon>
