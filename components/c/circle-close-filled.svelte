<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfuht3bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tfuht3bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:circle-close-filled" {...props}></Icon>
