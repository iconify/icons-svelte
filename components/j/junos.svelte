<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhqf8nbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":512};
const content = `<path class="rhqf8nbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:junos" {...props}></Icon>
