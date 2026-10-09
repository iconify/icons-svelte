<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6b3i8cls.css';
import '../../css/x/xgcr5txor.css';
import '../../css/l/ls70j1bso.css';
import '../../css/v/vm6ftdb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f6b3i8cls"/><path class="xgcr5txor"/><path class="ls70j1bso"/><path class="vm6ftdb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-x-20" {...props}></Icon>
