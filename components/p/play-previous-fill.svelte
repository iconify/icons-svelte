<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_2tanqqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2tanqqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-previous-fill" {...props}></Icon>
