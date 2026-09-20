<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo-kk0baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo-kk0baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-arrow-up" {...props}></Icon>
