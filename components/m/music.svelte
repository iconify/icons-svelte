<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah-qa3bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah-qa3bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:music" {...props}></Icon>
