<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv5djrbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv5djrbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-roller-outline" {...props}></Icon>
