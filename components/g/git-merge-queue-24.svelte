<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8-ol_24k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-ol_24k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-merge-queue-24" {...props}></Icon>
