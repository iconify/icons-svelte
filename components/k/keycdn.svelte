<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjb21xt1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjb21xt1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:keycdn" {...props}></Icon>
