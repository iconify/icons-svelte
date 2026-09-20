<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpjc7qc9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpjc7qc9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bowl-mix" {...props}></Icon>
