<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydbm-jb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="ydbm-jb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dj" {...props}></Icon>
