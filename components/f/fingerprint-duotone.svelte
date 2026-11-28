<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yggk-nx0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yggk-nx0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fingerprint-duotone" {...props}></Icon>
