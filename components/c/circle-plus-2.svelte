<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s17h1ybel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s17h1ybel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-plus-2" {...props}></Icon>
