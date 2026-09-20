<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byz9vkb6r.css';
import '../../css/h/h_ma9rt0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="byz9vkb6r"/><path class="h_ma9rt0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:lock-closed-outline" {...props}></Icon>
