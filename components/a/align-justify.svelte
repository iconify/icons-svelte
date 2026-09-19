<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcvn449qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcvn449qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:align-justify" {...props}></Icon>
