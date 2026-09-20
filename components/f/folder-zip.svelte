<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxen12e3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="lxen12e3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:folder-zip" {...props}></Icon>
