<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdib-abbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdib-abbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:circle-left" {...props}></Icon>
