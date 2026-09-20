<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzq7745mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzq7745mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-up-large-duotone" {...props}></Icon>
