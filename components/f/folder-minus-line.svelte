<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqk1bib6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqk1bib6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-minus-line" {...props}></Icon>
