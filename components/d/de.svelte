<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yzfkwyb_b.css';
import '../../css/c/cu3su9ffu.css';
import '../../css/o/o1sk4_0cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yzfkwyb_b"/><path class="cu3su9ffu"/><path class="o1sk4_0cf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:de" {...props}></Icon>
