<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nycn5mb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nycn5mb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-shape-up-to-line" {...props}></Icon>
