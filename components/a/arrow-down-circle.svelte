<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lbgjelwtv.css';
import '../../css/w/wnddzdb0b.css';
import '../../css/a/arnnz_b1g.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lbgjelwtv"/><path class="wnddzdb0b"/><path class="arnnz_b1g"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:arrow-down-circle" {...props}></Icon>
