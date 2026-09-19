<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrfi2tgtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrfi2tgtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:group-filled" {...props}></Icon>
