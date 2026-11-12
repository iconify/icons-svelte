<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-9ihkig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8-9ihkig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:itsm-ng" {...props}></Icon>
