<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp3_0nbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp3_0nbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-open" {...props}></Icon>
