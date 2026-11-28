<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sck_21-ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sck_21-ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:paintbrush-solid" {...props}></Icon>
