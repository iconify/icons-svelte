<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-w1mof7v.css';
import '../../css/t/tt8n265dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b-w1mof7v"/><path class="tt8n265dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:induction-hob-20-bold" {...props}></Icon>
