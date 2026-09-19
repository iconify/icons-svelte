<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s23bnwb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":343,"height":512};
const content = `<path class="s23bnwb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cloudfoundry" {...props}></Icon>
