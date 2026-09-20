<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqjnrh82t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bqjnrh82t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:labels" {...props}></Icon>
