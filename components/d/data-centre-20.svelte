<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw69dfdzg.css';
import '../../css/n/nb8b6vbgg.css';
import '../../css/i/i52nyunzx.css';
import '../../css/b/bon82pb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dw69dfdzg"/><path class="nb8b6vbgg"/><path class="i52nyunzx"/><path class="bon82pb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:data-centre-20" {...props}></Icon>
