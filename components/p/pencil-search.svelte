<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnq9-21ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnq9-21ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-search" {...props}></Icon>
