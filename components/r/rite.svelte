<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7eyqi9kg.css';
import '../../css/e/eujo24bzi.css';
import '../../css/h/h13wcxb2s.css';
import '../../css/h/h7dqv975i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7eyqi9kg"/><path class="eujo24bzi"/><path class="h13wcxb2s"/><path class="h7dqv975i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rite" {...props}></Icon>
