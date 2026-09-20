<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bha5ecbwn.css';
import '../../css/p/p078on3jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bha5ecbwn"/><path clip-rule="evenodd" class="p078on3jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ronin" {...props}></Icon>
