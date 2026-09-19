<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elnfgwwuk.css';
import '../../css/u/u5h-mpcos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elnfgwwuk"/><circle class="u5h-mpcos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:compass-1" {...props}></Icon>
