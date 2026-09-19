<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4dpjs72k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m4dpjs72k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:girl-small-filled" {...props}></Icon>
