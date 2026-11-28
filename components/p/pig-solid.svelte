<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibp3gfb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibp3gfb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pig-solid" {...props}></Icon>
