<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spyhg9e6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spyhg9e6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pill-plus" {...props}></Icon>
