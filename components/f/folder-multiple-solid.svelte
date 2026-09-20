<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7rms6bun.css';
import '../../css/p/pnnc77hwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7rms6bun"/><path class="pnnc77hwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-multiple-solid" {...props}></Icon>
