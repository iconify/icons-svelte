<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxb8ywse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioxb8ywse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:json" {...props}></Icon>
