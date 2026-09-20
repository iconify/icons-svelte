<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw1itqbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw1itqbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bolt-lightning" {...props}></Icon>
