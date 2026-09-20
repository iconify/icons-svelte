<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9s7-rhuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9s7-rhuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:overcast-logo-solid" {...props}></Icon>
