<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwvj0zbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwvj0zbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:collapse-all" {...props}></Icon>
