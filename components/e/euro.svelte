<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-5recc8q.css';
import '../../css/i/i7-pdt9kj.css';
import '../../css/i/i9ivp18un.css';
import '../../css/s/s-cle7bfv.css';
import '../../css/q/qzmw8qbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f-5recc8q wm-k"/><path class="i7-pdt9kj wm-k"/><path class="i9ivp18un wm-k"/><path class="s-cle7bfv wm-shine"/><path class="qzmw8qbfy wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:euro" {...props}></Icon>
