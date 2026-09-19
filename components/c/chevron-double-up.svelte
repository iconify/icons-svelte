<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn4p--2fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn4p--2fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:chevron-double-up" {...props}></Icon>
