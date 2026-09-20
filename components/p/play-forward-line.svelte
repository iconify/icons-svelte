<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-x2zkbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-x2zkbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-forward-line" {...props}></Icon>
