<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyrr1ab6u.css';
import '../../css/v/vtpfxs3yr.css';
import '../../css/o/oebxy1zud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dyrr1ab6u"/><path class="vtpfxs3yr"/><path class="oebxy1zud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-bond-20-bold" {...props}></Icon>
