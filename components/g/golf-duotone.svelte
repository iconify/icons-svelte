<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcca3lbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vcca3lbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:golf-duotone" {...props}></Icon>
