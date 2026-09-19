<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im-34tlgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="im-34tlgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cursor-arrow-small-filled" {...props}></Icon>
