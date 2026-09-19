<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x80f4s0za.css';
import '../../css/y/yu1gnvz7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x80f4s0za"/><path class="yu1gnvz7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:container-outlined" {...props}></Icon>
