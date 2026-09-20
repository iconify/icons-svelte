<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxpm_3bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxpm_3bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:creative-commons-pd" {...props}></Icon>
