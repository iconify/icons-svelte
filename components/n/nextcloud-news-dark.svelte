<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ood9f2bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ood9f2bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-news-dark" {...props}></Icon>
