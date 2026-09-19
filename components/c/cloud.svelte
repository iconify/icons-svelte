<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhgh78ojh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhgh78ojh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:cloud" {...props}></Icon>
