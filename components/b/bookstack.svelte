<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozl6xx3lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozl6xx3lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bookstack" {...props}></Icon>
