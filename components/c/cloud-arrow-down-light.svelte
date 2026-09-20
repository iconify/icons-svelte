<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm8d_x7vj.css';
import '../../css/r/rdm-ltbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm8d_x7vj"/><path class="rdm-ltbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-arrow-down-light" {...props}></Icon>
