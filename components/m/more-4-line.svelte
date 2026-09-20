<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldjtx9lab.css';
import '../../css/m/mrqn0ob3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldjtx9lab"/><path class="mrqn0ob3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-4-line" {...props}></Icon>
