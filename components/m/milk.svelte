<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d7odni4zo.css';
import '../../css/p/pcozc4xmy.css';
import '../../css/s/sg1dwbdru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d7odni4zo"/><path class="pcozc4xmy"/><path class="sg1dwbdru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:milk" {...props}></Icon>
