<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obkeojb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obkeojb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-alt-1-duotone" {...props}></Icon>
