<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8xxkabrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":457,"height":512};
const content = `<path class="o8xxkabrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:expo" {...props}></Icon>
