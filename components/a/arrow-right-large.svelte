<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6nnl5bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6nnl5bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-right-large" {...props}></Icon>
