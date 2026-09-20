<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqkmd_7zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqkmd_7zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:link-broken2" {...props}></Icon>
