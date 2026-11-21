<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_0y3m6li.css';
import '../../css/b/b6hy8accx.css';
import '../../css/i/igxotebur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_0y3m6li"/><path class="b6hy8accx"/><path class="igxotebur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-hail-filled" {...props}></Icon>
