<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp94h521r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp94h521r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:code-ai" {...props}></Icon>
