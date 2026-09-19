<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z748_ebdy.css';
import '../../css/e/e7vpmh2zb.css';
import '../../css/z/zsw4udyjx.css';
import '../../css/z/zvp_pt6pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="z748_ebdy"/><path class="e7vpmh2zb"/><path class="zsw4udyjx"/><path class="zvp_pt6pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ph-4x3" {...props}></Icon>
