<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmrm4zbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmrm4zbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-store" {...props}></Icon>
