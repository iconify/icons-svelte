<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebq0opbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebq0opbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-filled" {...props}></Icon>
