<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ziswbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ziswbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-9-plus-box-outline" {...props}></Icon>
