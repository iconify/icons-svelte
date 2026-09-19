<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dob_ddbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dob_ddbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:anyway-fm" {...props}></Icon>
