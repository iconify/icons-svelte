<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hutpv5bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hutpv5bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grid-goldenratio" {...props}></Icon>
