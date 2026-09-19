<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s741nbbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s741nbbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:heart-solid" {...props}></Icon>
