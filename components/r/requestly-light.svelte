<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9lsb3wir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9lsb3wir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:requestly-light" {...props}></Icon>
