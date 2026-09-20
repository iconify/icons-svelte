<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuu-fnbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuu-fnbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:myget" {...props}></Icon>
