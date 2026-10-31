<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ephwb-o.css';
import '../../css/g/gk5dn-bts.css';
import '../../css/r/r6ariacwh.css';
import '../../css/z/z00sw9avu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="gk5dn-bts"/><path class="r6ariacwh"/><path class="z00sw9avu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:kuwait" {...props}></Icon>
