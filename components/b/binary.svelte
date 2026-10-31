<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/n0p4rlb9a.css';
import '../../css/u/u40auj6vj.css';
import '../../css/t/tz3moq2rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="n0p4rlb9a wm-shadow"/><path class="u40auj6vj wm-shadow"/><path class="tz3moq2rq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:binary" {...props}></Icon>
