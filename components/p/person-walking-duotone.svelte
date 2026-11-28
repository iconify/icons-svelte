<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwk5qtb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vwk5qtb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:person-walking-duotone" {...props}></Icon>
