<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkc96qbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkc96qbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:penpot" {...props}></Icon>
