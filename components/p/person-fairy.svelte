<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxx5cbc5a.css';
import '../../css/t/tof8bjbhp.css';
import '../../css/v/vm8glirhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="hxx5cbc5a"/><path class="tof8bjbhp"/><path class="vm8glirhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-fairy" {...props}></Icon>
