<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exv5f0b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":488};
const content = `<path class="exv5f0b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:evernote" {...props}></Icon>
