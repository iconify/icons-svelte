<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygnd17bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygnd17bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-alert" {...props}></Icon>
