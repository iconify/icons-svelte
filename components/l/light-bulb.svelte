<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj95-5_rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj95-5_rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:light-bulb" {...props}></Icon>
