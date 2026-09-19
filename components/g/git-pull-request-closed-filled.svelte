<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx3v0_qti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx3v0_qti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-pull-request-closed-filled" {...props}></Icon>
