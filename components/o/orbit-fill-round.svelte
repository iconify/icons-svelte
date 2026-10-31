<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmwcp1byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmwcp1byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:orbit-fill-round" {...props}></Icon>
