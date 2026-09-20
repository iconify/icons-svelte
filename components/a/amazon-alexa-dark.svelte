<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya9w77bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya9w77bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-alexa-dark" {...props}></Icon>
