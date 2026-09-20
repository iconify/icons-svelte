<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpcu1cy2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpcu1cy2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-70-small" {...props}></Icon>
