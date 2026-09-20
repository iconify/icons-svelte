<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m--alzbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m--alzbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-escape-duotone" {...props}></Icon>
