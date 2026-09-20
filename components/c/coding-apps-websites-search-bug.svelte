<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6k8e83ng.css';
import '../../css/x/x8w8erb9x.css';
import '../../css/k/ka7_tbczt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f6k8e83ng"/><path class="x8w8erb9x"/><path class="ka7_tbczt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:coding-apps-websites-search-bug" {...props}></Icon>
