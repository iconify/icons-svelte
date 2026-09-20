<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmkr0povj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmkr0povj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:plane-departure" {...props}></Icon>
