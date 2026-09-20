<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuc7ebrqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uuc7ebrqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:industry-15" {...props}></Icon>
