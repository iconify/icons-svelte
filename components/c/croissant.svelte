<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vjuwjpbva.css';
import '../../css/u/u6380db6s.css';
import '../../css/g/g-903w19m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vjuwjpbva"/><path class="u6380db6s"/><path class="g-903w19m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:croissant" {...props}></Icon>
