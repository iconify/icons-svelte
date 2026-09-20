<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_dx3d6ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_dx3d6ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-10-small" {...props}></Icon>
