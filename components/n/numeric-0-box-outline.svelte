<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwn8_7bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwn8_7bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-0-box-outline" {...props}></Icon>
