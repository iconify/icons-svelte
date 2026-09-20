<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2tn1duup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2tn1duup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-rss-filled" {...props}></Icon>
