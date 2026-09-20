<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm335wbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm335wbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-9-filled" {...props}></Icon>
