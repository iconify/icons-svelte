<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqe1m0bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zqe1m0bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:jeans" {...props}></Icon>
