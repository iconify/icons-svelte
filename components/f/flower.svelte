<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqvur-jub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="yqvur-jub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flower" {...props}></Icon>
