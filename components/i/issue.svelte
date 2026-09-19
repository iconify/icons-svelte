<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c318b6b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c318b6b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:issue" {...props}></Icon>
