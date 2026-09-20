<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adhxuu-rl.css';
import '../../css/l/l520-dkdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adhxuu-rl"/><path class="l520-dkdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pinejs" {...props}></Icon>
