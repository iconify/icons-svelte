<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvnprm43r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvnprm43r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hard-drive-1-bold" {...props}></Icon>
