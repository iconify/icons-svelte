<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-3toiuuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-3toiuuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:heart" {...props}></Icon>
