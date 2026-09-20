<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry6canfiv.css';
import '../../css/r/re9d9lkhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry6canfiv"/><path class="re9d9lkhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:balance-light" {...props}></Icon>
