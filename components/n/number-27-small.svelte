<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm2pr3awq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm2pr3awq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-27-small" {...props}></Icon>
