<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6valsw2k.css';
import '../../css/y/ypft5mbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6valsw2k"/><path class="ypft5mbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-forwarded-fill" {...props}></Icon>
