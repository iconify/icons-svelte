<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u2e6n6bfm.css';
import '../../css/e/eibcigs-u.css';
import '../../css/s/somstlbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u2e6n6bfm"/><path class="eibcigs-u"/><path class="somstlbkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:installing-updates-02" {...props}></Icon>
