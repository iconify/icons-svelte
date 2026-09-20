<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwklj_a9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xwklj_a9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-down-solid" {...props}></Icon>
