<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d598p2b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d598p2b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-down-solid" {...props}></Icon>
