<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugku64bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":512};
const content = `<path class="ugku64bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:influxdata" {...props}></Icon>
