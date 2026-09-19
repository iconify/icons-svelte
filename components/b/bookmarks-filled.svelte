<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r99wp1s3m.css';
import '../../css/h/h41dyrd2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r99wp1s3m"/><path class="h41dyrd2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmarks-filled" {...props}></Icon>
