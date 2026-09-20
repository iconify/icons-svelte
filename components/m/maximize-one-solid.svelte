<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0qxbff3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0qxbff3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:maximize-one-solid" {...props}></Icon>
