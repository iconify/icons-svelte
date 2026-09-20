<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpvtkxbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpvtkxbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-down-wide-narrow" {...props}></Icon>
