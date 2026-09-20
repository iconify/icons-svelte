<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt4wtjaxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt4wtjaxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-left-large" {...props}></Icon>
