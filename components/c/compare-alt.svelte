<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql0f65czi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b ql0f65czi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:compare-alt" {...props}></Icon>
