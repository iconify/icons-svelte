<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n_ig5ib1q.css';
import '../../css/a/avqyneb1s.css';
import '../../css/k/ksawrcf5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n_ig5ib1q"/><path class="avqyneb1s"/><path class="ksawrcf5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:intersect" {...props}></Icon>
