<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9on-9b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d9on-9b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:cherry-pick-commit" {...props}></Icon>
