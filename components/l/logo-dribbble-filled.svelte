<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo7mz2bml.css';
import '../../css/n/nuz4awhaa.css';
import '../../css/a/a6uabbbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo7mz2bml"/><path class="nuz4awhaa"/><path class="a6uabbbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-dribbble-filled" {...props}></Icon>
