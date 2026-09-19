<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q_aeo3bes.css';
import '../../css/h/h9q6cw2rm.css';
import '../../css/b/bnoq2abfn.css';
import '../../css/m/m9h5tppbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="q_aeo3bes"/><path class="h9q6cw2rm"/><path class="bnoq2abfn"/><path class="m9h5tppbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:bell-with-slash" {...props}></Icon>
