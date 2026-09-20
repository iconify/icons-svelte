<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckyq5qvae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckyq5qvae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:at-solid" {...props}></Icon>
