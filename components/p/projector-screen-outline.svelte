<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj-ns2bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj-ns2bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:projector-screen-outline" {...props}></Icon>
