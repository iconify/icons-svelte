<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abai76h0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abai76h0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-repository-fill" {...props}></Icon>
