<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hib7fibeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hib7fibeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:json-ld1" {...props}></Icon>
