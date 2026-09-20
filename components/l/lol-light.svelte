<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m7pevhgad.css';
import '../../css/d/dgll2bd_b.css';
import '../../css/q/q9cootb2b.css';
import '../../css/r/rwwgm7bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="m7pevhgad"/><circle class="dgll2bd_b"/><circle class="q9cootb2b"/><path clip-rule="evenodd" class="rwwgm7bpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lol-light" {...props}></Icon>
