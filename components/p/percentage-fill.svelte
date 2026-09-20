<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2rhc9bli.css';
import '../../css/j/j4be6p33p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2rhc9bli"/><path class="j4be6p33p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:percentage-fill" {...props}></Icon>
