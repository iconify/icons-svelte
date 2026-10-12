<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eioub-k-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eioub-k-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:concierge-bell-filled" {...props}></Icon>
