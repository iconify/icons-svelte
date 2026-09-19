<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knp2qb6bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="knp2qb6bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:get-pocket" {...props}></Icon>
