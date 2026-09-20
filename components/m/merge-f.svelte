<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3hoj7_rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="s3hoj7_rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:merge-f" {...props}></Icon>
