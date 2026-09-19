<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqn3_72mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqn3_72mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-down" {...props}></Icon>
