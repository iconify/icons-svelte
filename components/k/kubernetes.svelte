<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi4d1ebgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yi4d1ebgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kubernetes" {...props}></Icon>
