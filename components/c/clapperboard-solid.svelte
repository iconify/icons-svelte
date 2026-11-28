<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8y5n6-du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8y5n6-du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clapperboard-solid" {...props}></Icon>
