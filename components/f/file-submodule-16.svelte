<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbntjqb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tbntjqb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-submodule-16" {...props}></Icon>
