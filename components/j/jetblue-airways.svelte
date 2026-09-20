<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grkthnbuz.css';
import '../../css/z/z46kzigug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grkthnbuz"/><path class="z46kzigug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jetblue-airways" {...props}></Icon>
