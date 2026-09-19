<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz7du6xnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz7du6xnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:checkmark-outline" {...props}></Icon>
