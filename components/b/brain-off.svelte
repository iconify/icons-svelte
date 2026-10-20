<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lr_5gbo5a.css';
import '../../css/q/qj9kuabzc.css';
import '../../css/d/d5qwpt3kx.css';
import '../../css/i/i37yl4fkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lr_5gbo5a"/><path class="qj9kuabzc"/><path class="d5qwpt3kx"/><path class="i37yl4fkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:brain-off" {...props}></Icon>
