<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wczcb9hcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wczcb9hcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:container-filled" {...props}></Icon>
