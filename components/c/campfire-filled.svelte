<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kti4eo0qw.css';
import '../../css/n/n7mu1nbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kti4eo0qw"/><path class="n7mu1nbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:campfire-filled" {...props}></Icon>
