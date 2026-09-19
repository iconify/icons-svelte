<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqbhp9bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqbhp9bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:export" {...props}></Icon>
