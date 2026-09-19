<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpwo_ibfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpwo_ibfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:invision" {...props}></Icon>
