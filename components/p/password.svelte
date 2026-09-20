<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9w17pbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9w17pbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:password" {...props}></Icon>
