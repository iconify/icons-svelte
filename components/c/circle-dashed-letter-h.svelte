<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w91fff93j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w91fff93j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-h" {...props}></Icon>
