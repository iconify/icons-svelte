<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h0dqwzvmd.css';
import '../../css/i/i_anfsynt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h0dqwzvmd"/><path class="i_anfsynt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kukai" {...props}></Icon>
