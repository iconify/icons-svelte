<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2q3mcg-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2q3mcg-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-center" {...props}></Icon>
