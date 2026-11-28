<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaxykhbwe.css';
import '../../css/i/idwsbdxlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary uaxykhbwe"/><path class="idwsbdxlg primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-down-duo" {...props}></Icon>
