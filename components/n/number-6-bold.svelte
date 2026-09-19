<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/argz2yb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="argz2yb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-6-bold" {...props}></Icon>
