<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggyrz3unk.css';
import '../../css/c/ci8zk7bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ggyrz3unk"/><path class="ci8zk7bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fast-forward-20-bold" {...props}></Icon>
