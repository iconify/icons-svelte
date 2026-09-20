<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oooywdbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oooywdbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:picnic-table" {...props}></Icon>
