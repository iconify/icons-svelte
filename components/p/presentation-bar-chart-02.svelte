<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f3w91ubqa.css';
import '../../css/j/j1-zg0xja.css';
import '../../css/t/tow7vpjog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f3w91ubqa"/><path class="j1-zg0xja"/><path class="tow7vpjog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:presentation-bar-chart-02" {...props}></Icon>
