<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrw2yvb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrw2yvb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pliers-solid" {...props}></Icon>
