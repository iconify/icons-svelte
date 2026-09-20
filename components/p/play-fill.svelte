<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p063ujoxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p063ujoxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:play-fill" {...props}></Icon>
