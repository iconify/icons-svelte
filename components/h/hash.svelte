<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q320efsbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q320efsbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hash" {...props}></Icon>
