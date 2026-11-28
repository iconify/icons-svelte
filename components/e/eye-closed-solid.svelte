<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v412_cb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v412_cb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:eye-closed-solid" {...props}></Icon>
