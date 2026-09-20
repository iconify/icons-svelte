<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzc1c8a6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bzc1c8a6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:group-meeting-call-remix" {...props}></Icon>
