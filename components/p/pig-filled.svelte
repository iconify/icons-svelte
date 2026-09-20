<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiq-huvyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiq-huvyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pig-filled" {...props}></Icon>
