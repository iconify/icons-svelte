<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz34yrbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nz34yrbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:projector" {...props}></Icon>
