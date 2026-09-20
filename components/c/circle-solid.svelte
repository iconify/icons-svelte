<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtitn8o0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtitn8o0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:circle-solid" {...props}></Icon>
