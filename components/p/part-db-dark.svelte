<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de43k29rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="de43k29rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:part-db-dark" {...props}></Icon>
