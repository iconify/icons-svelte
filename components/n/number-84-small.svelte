<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdpmnubth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdpmnubth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-84-small" {...props}></Icon>
