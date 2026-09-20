<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9ce1qk7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9ce1qk7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bread" {...props}></Icon>
