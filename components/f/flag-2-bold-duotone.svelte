<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq6b85b-a.css';
import '../../css/q/qku8lwbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq6b85b-a"/><path class="qku8lwbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-2-bold-duotone" {...props}></Icon>
