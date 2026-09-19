<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih88xyvhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ih88xyvhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bo-blog" {...props}></Icon>
