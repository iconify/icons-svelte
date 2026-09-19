<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c97hp8b9o.css';
import '../../css/u/unr_8tk5x.css';
import '../../css/a/apilembcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c97hp8b9o"/><path class="unr_8tk5x"/><path class="apilembcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:book-up-2" {...props}></Icon>
