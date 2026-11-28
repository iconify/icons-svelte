<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhx9fhbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhx9fhbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:accent-grave-solid" {...props}></Icon>
