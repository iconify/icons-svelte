<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_2t8xb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_2t8xb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:egg" {...props}></Icon>
