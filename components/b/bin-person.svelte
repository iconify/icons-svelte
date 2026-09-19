<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kebdum4nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kebdum4nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:bin-person" {...props}></Icon>
