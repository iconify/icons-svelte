<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygwp1gb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygwp1gb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-5" {...props}></Icon>
