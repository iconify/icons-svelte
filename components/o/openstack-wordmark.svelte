<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq4jivysn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="eq4jivysn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:openstack-wordmark" {...props}></Icon>
