<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz1z3f7on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz1z3f7on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-0-small" {...props}></Icon>
