<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uevygjbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uevygjbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-90-small" {...props}></Icon>
