<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fzg-nyb4e.css';
import '../../css/s/s6d007y7k.css';
import '../../css/c/c3jjas9nf.css';
import '../../css/i/id2d1md9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fzg-nyb4e"/><path class="s6d007y7k"/><path class="c3jjas9nf"/><path class="id2d1md9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:button" {...props}></Icon>
