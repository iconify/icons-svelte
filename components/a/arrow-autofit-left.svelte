<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmjiwu9pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmjiwu9pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-left" {...props}></Icon>
