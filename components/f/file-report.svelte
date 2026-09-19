<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5d7qab8q.css';
import '../../css/j/j4nbmzbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5d7qab8q"/><path class="j4nbmzbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-report" {...props}></Icon>
