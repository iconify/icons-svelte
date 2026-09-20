<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkjlr2bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bkjlr2bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:project" {...props}></Icon>
