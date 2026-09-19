<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x80qvwb-u.css';
import '../../css/b/b63gy5bbo.css';
import '../../css/c/c8--srbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x80qvwb-u"/><path class="b63gy5bbo"/><path class="c8--srbre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-arrow-up-right-02" {...props}></Icon>
