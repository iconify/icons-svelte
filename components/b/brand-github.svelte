<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq__wbbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq__wbbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-github" {...props}></Icon>
