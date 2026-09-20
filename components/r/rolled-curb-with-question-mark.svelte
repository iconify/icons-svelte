<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqu27-g1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bqu27-g1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rolled-curb-with-question-mark" {...props}></Icon>
