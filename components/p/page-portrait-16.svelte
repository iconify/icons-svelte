<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5fc605jj.css';
import '../../css/v/vrumybbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5fc605jj"/><path clip-rule="evenodd" class="vrumybbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:page-portrait-16" {...props}></Icon>
