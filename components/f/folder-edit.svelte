<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_s6lc4vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_s6lc4vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-edit" {...props}></Icon>
