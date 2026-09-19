<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u6x25je3c.css';
import '../../css/l/l9wcuz8dq.css';
import '../../css/m/mchh0pr4c.css';
import '../../css/l/lbbeo5bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="u6x25je3c"/><path class="l9wcuz8dq"/><path class="mchh0pr4c"/><path class="lbbeo5bez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:lungs" {...props}></Icon>
