<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juq__jbid.css';
import '../../css/n/nh76xtbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="juq__jbid"/><path class="nh76xtbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-pointer-ban-filled" {...props}></Icon>
