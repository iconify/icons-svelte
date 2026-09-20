<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuwh7k_9h.css';
import '../../css/q/qo3rhxb4p.css';
import '../../css/i/i7sr6ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuwh7k_9h"/><path class="qo3rhxb4p"/><path class="i7sr6ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-alt-circle-down" {...props}></Icon>
