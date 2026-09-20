<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxlq8b69v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxlq8b69v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-twelve" {...props}></Icon>
