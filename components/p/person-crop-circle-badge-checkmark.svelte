<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng6blccig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ng6blccig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-circle-badge-checkmark" {...props}></Icon>
