<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgk128bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgk128bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-many-to-zero-or-many" {...props}></Icon>
