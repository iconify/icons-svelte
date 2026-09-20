<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opccw0okt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opccw0okt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-user-fill" {...props}></Icon>
