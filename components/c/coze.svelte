<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0j2kb17q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0j2kb17q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:coze" {...props}></Icon>
