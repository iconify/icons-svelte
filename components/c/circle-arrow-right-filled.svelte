<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmfj55_qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmfj55_qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-arrow-right-filled" {...props}></Icon>
