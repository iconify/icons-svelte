<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5of6ybso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5of6ybso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clover-2" {...props}></Icon>
