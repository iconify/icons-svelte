<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it_isbcep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it_isbcep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:graduation-cap" {...props}></Icon>
