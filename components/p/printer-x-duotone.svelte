<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/imhm0cmas.css';
import '../../css/v/v0rsyqbxa.css';
import '../../css/h/hnbud8kdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="imhm0cmas"/><path class="v0rsyqbxa"/><path class="hnbud8kdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:printer-x-duotone" {...props}></Icon>
