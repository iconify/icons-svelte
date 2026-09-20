<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5lczrbjj.css';
import '../../css/w/w_gjrzbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5lczrbjj"/><path class="w_gjrzbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-edit-bold" {...props}></Icon>
