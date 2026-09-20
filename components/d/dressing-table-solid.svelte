<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix6phcbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ix6phcbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dressing-table-solid" {...props}></Icon>
