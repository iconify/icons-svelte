<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwiuv55ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iwiuv55ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-models" {...props}></Icon>
