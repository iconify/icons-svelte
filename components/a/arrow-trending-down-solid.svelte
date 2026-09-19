<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpi9_ac9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpi9_ac9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-trending-down-solid" {...props}></Icon>
