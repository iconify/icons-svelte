<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgjuh8b2j.css';
import '../../css/z/zqpq1rb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgjuh8b2j"/><path class="zqpq1rb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:feather-filled" {...props}></Icon>
