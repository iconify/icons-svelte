<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7zwtsbyj.css';
import '../../css/m/mch1fnkdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="d7zwtsbyj"/><path class="mch1fnkdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-file-duotone-fill" {...props}></Icon>
