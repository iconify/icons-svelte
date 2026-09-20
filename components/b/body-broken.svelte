<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny4i4fb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4i4fb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-broken" {...props}></Icon>
