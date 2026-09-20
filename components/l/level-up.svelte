<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc4n_nfpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wc4n_nfpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:level-up" {...props}></Icon>
