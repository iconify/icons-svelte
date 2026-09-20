<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww7cr52rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ww7cr52rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:fashion-accessories" {...props}></Icon>
