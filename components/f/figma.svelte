<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/e/ewabcgb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><circle class="aqhok2bbj"/><path class="ewabcgb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:figma" {...props}></Icon>
