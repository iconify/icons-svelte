<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kofy-7b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kofy-7b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-moon-lightning-solid" {...props}></Icon>
