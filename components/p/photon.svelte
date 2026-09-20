<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay0p6rq1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay0p6rq1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:photon" {...props}></Icon>
