<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wey8zoa3m.css';
import '../../css/v/vcmk6cc8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wey8zoa3m"/><path class="vcmk6cc8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:messages-circle-filled" {...props}></Icon>
