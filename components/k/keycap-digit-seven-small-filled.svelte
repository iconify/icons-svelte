<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpr0hcbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mpr0hcbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-seven-small-filled" {...props}></Icon>
