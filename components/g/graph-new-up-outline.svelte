<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj6z6-b0q.css';
import '../../css/p/p9-c1gbhj.css';
import '../../css/e/eo7u7db2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj6z6-b0q"/><path clip-rule="evenodd" class="p9-c1gbhj"/><path class="eo7u7db2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-new-up-outline" {...props}></Icon>
