<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/govcx3bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="govcx3bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:factr" {...props}></Icon>
