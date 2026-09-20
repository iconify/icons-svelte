<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/i/ivjvz2eii.css';
import '../../css/j/j-hc1kblh.css';
import '../../css/t/tvg4rybvu.css';
import '../../css/b/bd9gczbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGXJkKzvJi"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="j-hc1kblh"/><path class="tvg4rybvu"/></g></mask></defs><circle mask="url(#SVGXJkKzvJi)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:plus-circle-filled" {...props}></Icon>
