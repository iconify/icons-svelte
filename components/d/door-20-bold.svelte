<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6120wbdh.css';
import '../../css/b/bdrmmtuqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v6120wbdh"/><path class="bdrmmtuqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:door-20-bold" {...props}></Icon>
