<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfmo26buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yfmo26buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-10-remix" {...props}></Icon>
