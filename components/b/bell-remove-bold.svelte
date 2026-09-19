<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fossymb9j.css';
import '../../css/n/n_fh7yyal.css';
import '../../css/y/yo32qf32j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fossymb9j"/><path clip-rule="evenodd" class="n_fh7yyal"/><path class="yo32qf32j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-remove-bold" {...props}></Icon>
