<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saj1_ob7a.css';
import '../../css/b/bzm068cfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="saj1_ob7a"/><path class="bzm068cfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readmeabook-light" {...props}></Icon>
