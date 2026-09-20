<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0hb15zdf.css';
import '../../css/n/nifbesbdu.css';
import '../../css/z/zn93f2bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0hb15zdf"/><path class="nifbesbdu"/><path class="zn93f2bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:biso" {...props}></Icon>
