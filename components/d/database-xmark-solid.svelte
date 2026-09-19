<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aei0xrbup.css';
import '../../css/p/pl9_uwwwt.css';
import '../../css/j/j5_gj04sw.css';
import '../../css/e/en7mfccjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="aei0xrbup"/><path clip-rule="evenodd" class="pl9_uwwwt"/><path clip-rule="evenodd" class="j5_gj04sw"/><path class="en7mfccjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:database-xmark-solid" {...props}></Icon>
