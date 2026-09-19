<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltikhp55e.css';
import '../../css/i/i4nkalbtd.css';
import '../../css/u/uykw5abjm.css';
import '../../css/g/gfprm-lkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ltikhp55e"/><path class="i4nkalbtd"/><path class="uykw5abjm"/><path class="gfprm-lkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apify-wordmark" {...props}></Icon>
