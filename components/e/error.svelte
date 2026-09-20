<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwefbqb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwefbqb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:error" {...props}></Icon>
