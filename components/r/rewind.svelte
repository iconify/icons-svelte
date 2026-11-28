<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrh1fac9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrh1fac9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rewind" {...props}></Icon>
