<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uki0vkbrr.css';
import '../../css/s/su9dknbed.css';
import '../../css/u/utr_d7_ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uki0vkbrr"/><path class="su9dknbed"/><path class="utr_d7_ko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:file-export-light" {...props}></Icon>
