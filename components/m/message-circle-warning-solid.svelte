<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m90tfysgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m90tfysgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-warning-solid" {...props}></Icon>
