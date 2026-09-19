<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rmf30cp6v.css';
import '../../css/r/rgxw0pbfu.css';
import '../../css/w/w55sklzjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rmf30cp6v"/><path class="rgxw0pbfu"/><path class="w55sklzjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:pouting-face" {...props}></Icon>
