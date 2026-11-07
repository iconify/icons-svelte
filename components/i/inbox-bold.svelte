<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k98gnnbfh.css';
import '../../css/v/voeniibqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k98gnnbfh"/><path class="voeniibqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-bold" {...props}></Icon>
