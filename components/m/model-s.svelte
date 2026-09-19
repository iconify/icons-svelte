<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u45v42bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u45v42bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:model-s" {...props}></Icon>
