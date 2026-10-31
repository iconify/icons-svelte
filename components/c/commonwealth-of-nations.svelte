<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7wfo1l2j.css';
import '../../css/h/hpwczr9zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="g7wfo1l2j"/><path class="hpwczr9zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:commonwealth-of-nations" {...props}></Icon>
