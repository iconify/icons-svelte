<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unur3-b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unur3-b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:minus-square-fill" {...props}></Icon>
