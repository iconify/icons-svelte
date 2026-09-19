<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r416zeb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r416zeb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-info-filled" {...props}></Icon>
