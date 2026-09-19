<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brmlh4b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="brmlh4b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-ttf-filled" {...props}></Icon>
