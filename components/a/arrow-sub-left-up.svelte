<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq4lwtbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq4lwtbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-sub-left-up" {...props}></Icon>
