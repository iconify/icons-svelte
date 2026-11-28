<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxlqh4btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxlqh4btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bot-gear" {...props}></Icon>
