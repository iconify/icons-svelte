<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgje56boo.css';
import '../../css/y/ymxiy1_5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zgje56boo"/><path class="ymxiy1_5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-check-16" {...props}></Icon>
