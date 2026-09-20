<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc2i8mbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc2i8mbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-78-small" {...props}></Icon>
