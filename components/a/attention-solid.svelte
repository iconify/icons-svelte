<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohf9olbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ohf9olbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:attention-solid" {...props}></Icon>
