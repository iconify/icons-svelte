<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu-nrmb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu-nrmb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paper-plane" {...props}></Icon>
