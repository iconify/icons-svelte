<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfbnew7sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfbnew7sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:lock-open" {...props}></Icon>
