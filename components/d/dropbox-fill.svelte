<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_hwnubhd.css';
import '../../css/u/ud9q8oepu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_hwnubhd"/><path class="ud9q8oepu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dropbox-fill" {...props}></Icon>
