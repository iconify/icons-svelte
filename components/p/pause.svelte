<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z46hmhu2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z46hmhu2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:pause" {...props}></Icon>
