<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um413-_bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um413-_bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-graph" {...props}></Icon>
