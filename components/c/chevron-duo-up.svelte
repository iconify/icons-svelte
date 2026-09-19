<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lny8fyb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lny8fyb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-duo-up" {...props}></Icon>
