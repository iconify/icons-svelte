<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iizqkmlih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iizqkmlih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:css3" {...props}></Icon>
