<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hadxb356p.css';
import '../../css/o/o8jdmjbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hadxb356p"/><path class="o8jdmjbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octoprint" {...props}></Icon>
