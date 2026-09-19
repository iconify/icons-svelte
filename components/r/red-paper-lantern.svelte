<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq35cqbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jq35cqbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:red-paper-lantern" {...props}></Icon>
