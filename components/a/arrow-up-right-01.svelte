<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/civj-4e9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="civj-4e9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-right-01" {...props}></Icon>
