<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq3f9xb0h.css';
import '../../css/v/vkpsfpb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nq3f9xb0h"/><path class="vkpsfpb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chainsaw-20" {...props}></Icon>
