<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4n791u6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":380,"height":790};
const content = `<path class="h4n791u6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:arrow-right" {...props}></Icon>
