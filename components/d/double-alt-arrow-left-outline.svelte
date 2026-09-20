<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf1q-gaub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf1q-gaub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-left-outline" {...props}></Icon>
