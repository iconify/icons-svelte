<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kul88tp0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kul88tp0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-roadmap-solid" {...props}></Icon>
