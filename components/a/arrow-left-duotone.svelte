<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8_ijmbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary x8_ijmbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-duotone" {...props}></Icon>
