<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9k5yp1vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9k5yp1vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hashtag-filled" {...props}></Icon>
