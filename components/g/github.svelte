<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5jqn4b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z5jqn4b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:github" {...props}></Icon>
