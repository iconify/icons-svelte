<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnkt3qb8k.css';
import '../../css/v/vl-e_fb9f.css';
import '../../css/f/f84_0wvks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qnkt3qb8k"/><path class="vl-e_fb9f"/><path class="f84_0wvks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flower-48" {...props}></Icon>
