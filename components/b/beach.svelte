<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pozf4vevq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pozf4vevq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:beach" {...props}></Icon>
