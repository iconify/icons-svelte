<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hst90xz2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hst90xz2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:repeat-alt-filled" {...props}></Icon>
