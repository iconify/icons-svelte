<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyv3hac8i.css';
import '../../css/x/xg50517th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyv3hac8i"/><path clip-rule="evenodd" class="xg50517th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:clover" {...props}></Icon>
