<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9afo1r9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9afo1r9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-right-fill-round" {...props}></Icon>
