<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3p6b1b2l.css';
import '../../css/z/z6ju0jldq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3p6b1b2l"/><path class="z6ju0jldq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-postman-open" {...props}></Icon>
