<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oav543bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oav543bla primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-duotone" {...props}></Icon>
