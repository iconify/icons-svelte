<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmi63dt4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmi63dt4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-to-zero-or-many" {...props}></Icon>
