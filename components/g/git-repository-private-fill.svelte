<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hor2v3luj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hor2v3luj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-repository-private-fill" {...props}></Icon>
