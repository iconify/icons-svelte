<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/ur3vzyb7h.css';
import '../../css/n/ndo8e3jvz.css';
import '../../css/j/jty3hzbzs.css';
import '../../css/c/c3_i8_3rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ur3vzyb7h wm-shadow"/><path class="ndo8e3jvz wm-shadow"/><path class="jty3hzbzs"/><path class="c3_i8_3rt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:menu" {...props}></Icon>
