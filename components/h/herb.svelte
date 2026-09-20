<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsk1vyb8u.css';
import '../../css/z/zpm02gbpx.css';
import '../../css/a/am34frbkn.css';
import '../../css/b/b9qb62bje.css';
import '../../css/n/nq4h-9b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tsk1vyb8u"/><path class="zpm02gbpx"/><path class="am34frbkn"/><path class="b9qb62bje"/><path class="nq4h-9b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:herb" {...props}></Icon>
