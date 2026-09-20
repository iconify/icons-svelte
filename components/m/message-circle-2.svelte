<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnk8b_buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnk8b_buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-2" {...props}></Icon>
