<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q09q9ermw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q09q9ermw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:home-active" {...props}></Icon>
