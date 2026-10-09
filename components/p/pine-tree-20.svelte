<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix3tztiqy.css';
import '../../css/s/sg1__vokg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ix3tztiqy"/><path class="sg1__vokg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pine-tree-20" {...props}></Icon>
