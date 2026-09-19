<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/g7ca5t3xz.css';
import '../../css/h/hitjxstjz.css';
import '../../css/q/qvtiz2hqe.css';
import '../../css/x/x9a0stbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="g7ca5t3xz"/><path class="hitjxstjz"/><path class="qvtiz2hqe"/><path class="x9a0stbbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:database-check-solid" {...props}></Icon>
