<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quhe-fjie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="quhe-fjie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-c2sc-small-filled" {...props}></Icon>
