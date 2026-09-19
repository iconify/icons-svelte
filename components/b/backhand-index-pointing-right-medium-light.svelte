<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/efl_o_l-c.css';
import '../../css/b/bg-i77b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(32 0) scale(-1 1)"><g class="ft5dv1b6b"><path class="efl_o_l-c"/><path class="bg-i77b7c"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:backhand-index-pointing-right-medium-light" {...props}></Icon>
