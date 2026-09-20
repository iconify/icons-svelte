<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdb6lnb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdb6lnb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-lock-open-outline" {...props}></Icon>
