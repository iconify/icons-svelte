<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/i8fkcybso.css';
import '../../css/n/nqmf4jucg.css';
import '../../css/u/up8qf57js.css';
import '../../css/k/kbhprvbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="i8fkcybso wm-shadow"/><path class="nqmf4jucg wm-shadow"/><path class="up8qf57js"/><path class="kbhprvbia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:factory" {...props}></Icon>
