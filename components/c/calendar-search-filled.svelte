<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwdovkx8c.css';
import '../../css/w/w3nlvcvue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwdovkx8c"/><path class="w3nlvcvue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-search-filled" {...props}></Icon>
