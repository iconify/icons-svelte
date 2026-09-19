<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-eltu37y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g-eltu37y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-down-from-line" {...props}></Icon>
