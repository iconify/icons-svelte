<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9r-36cdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9r-36cdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-content-filled" {...props}></Icon>
