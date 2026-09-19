<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbjrwhbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbjrwhbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:apple-full" {...props}></Icon>
