<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujcg1dbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ujcg1dbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handexpand" {...props}></Icon>
