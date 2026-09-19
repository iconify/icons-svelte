<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apk1qtb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="apk1qtb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-rm" {...props}></Icon>
