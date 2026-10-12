<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubfefht9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubfefht9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:between-vertical-end-filled" {...props}></Icon>
