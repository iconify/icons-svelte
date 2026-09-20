<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfg3yjb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="vfg3yjb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:messages-f" {...props}></Icon>
