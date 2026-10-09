<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9dzyiszx.css';
import '../../css/h/hfunc-u9d.css';
import '../../css/v/vm6ftdb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="hfunc-u9d"/><path class="vm6ftdb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-x-20" {...props}></Icon>
