<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_1u3cc3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_1u3cc3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-pie-2-filled" {...props}></Icon>
