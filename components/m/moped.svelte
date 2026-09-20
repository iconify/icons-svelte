<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oab43-7av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oab43-7av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:moped" {...props}></Icon>
