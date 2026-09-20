<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbgyefbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbgyefbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:join-bevel" {...props}></Icon>
