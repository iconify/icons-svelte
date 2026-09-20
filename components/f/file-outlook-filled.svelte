<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3i4310qw.css';
import '../../css/k/kd0bdubwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3i4310qw"/><path class="kd0bdubwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-outlook-filled" {...props}></Icon>
