<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em8j7dbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="em8j7dbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:musical-note-small" {...props}></Icon>
