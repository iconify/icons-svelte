<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr5t35m0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr5t35m0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-7-small" {...props}></Icon>
