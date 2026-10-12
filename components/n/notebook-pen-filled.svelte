<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv1b1wt7j.css';
import '../../css/h/hb1iu0uss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv1b1wt7j"/><path class="hb1iu0uss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:notebook-pen-filled" {...props}></Icon>
