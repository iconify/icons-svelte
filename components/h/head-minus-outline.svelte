<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts3yx7bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts3yx7bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-minus-outline" {...props}></Icon>
