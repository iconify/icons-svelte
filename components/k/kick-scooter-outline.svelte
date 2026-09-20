<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csyuqibvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csyuqibvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kick-scooter-outline" {...props}></Icon>
