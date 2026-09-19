<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0j6vybkj.css';
import '../../css/v/vytfc2c_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0j6vybkj"/><path class="vytfc2c_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-megaphone" {...props}></Icon>
