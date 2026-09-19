<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag8w_1_qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag8w_1_qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-1" {...props}></Icon>
