<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcu911z9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcu911z9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:jar-plus" {...props}></Icon>
