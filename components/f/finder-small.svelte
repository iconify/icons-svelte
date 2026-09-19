<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yojftwc6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yojftwc6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:finder-small" {...props}></Icon>
