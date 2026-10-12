<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uo6zw876u.css';
import '../../css/f/fzy50vbde.css';
import '../../css/r/rh3ihcc6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uo6zw876u"/><path class="fzy50vbde"/><path class="rh3ihcc6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paintbrush-vertical-duotone" {...props}></Icon>
