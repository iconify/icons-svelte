<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia-px2bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia-px2bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:custom-post-type" {...props}></Icon>
