<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og0hiob0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og0hiob0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-ordered-solid" {...props}></Icon>
