<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqk4wvbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eqk4wvbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:porkbun-light" {...props}></Icon>
