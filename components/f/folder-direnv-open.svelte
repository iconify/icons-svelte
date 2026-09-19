<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1crshb5u.css';
import '../../css/b/byrocu6aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h1crshb5u"/><path class="byrocu6aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-direnv-open" {...props}></Icon>
