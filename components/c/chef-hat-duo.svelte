<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n4hfolbfa.css';
import '../../css/o/o5ywef7nt.css';
import '../../css/t/te682eb5s.css';
import '../../css/g/g9owp9b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n4hfolbfa"/><path class="o5ywef7nt wm-a"/><path class="te682eb5s"/><path class="g9owp9b4k wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chef-hat-duo" {...props}></Icon>
