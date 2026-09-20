<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qubcu9bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qubcu9bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:arrow-up" {...props}></Icon>
