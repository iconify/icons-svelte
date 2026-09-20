<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlbz5b3ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mlbz5b3ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:qualcomm-logo-solid" {...props}></Icon>
