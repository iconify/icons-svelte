<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ytktbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":488};
const content = `<path class="h8ytktbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:linkedin-alt" {...props}></Icon>
