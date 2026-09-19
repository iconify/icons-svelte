<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqie4kb4q.css';
import '../../css/i/ifa7j6beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqie4kb4q"/><path class="ifa7j6beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:package-upgrade" {...props}></Icon>
