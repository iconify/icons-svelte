<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7ads4bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ads4bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-no-axes-column-decreasing" {...props}></Icon>
