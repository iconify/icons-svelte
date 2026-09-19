<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3231hb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s3231hb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face5-filled" {...props}></Icon>
