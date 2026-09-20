<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y06121bln.css';
import '../../css/q/qc3x1gn8n.css';
import '../../css/k/k0evexoqr.css';
import '../../css/o/o55rtrbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="y06121bln"/><path class="qc3x1gn8n"/><circle class="k0evexoqr"/><circle class="o55rtrbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:insta-duotone-line" {...props}></Icon>
