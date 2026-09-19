<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7f8r1bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7f8r1bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-9-bold" {...props}></Icon>
