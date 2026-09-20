<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwpraqpow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hwpraqpow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:link-diagonal" {...props}></Icon>
