<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njc_fzg-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="njc_fzg-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-type-test-case" {...props}></Icon>
