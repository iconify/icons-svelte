<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnvd4kpgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnvd4kpgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heart" {...props}></Icon>
