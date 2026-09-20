<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk9pi6bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk9pi6bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tapd" {...props}></Icon>
