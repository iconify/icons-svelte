<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkclc-bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkclc-bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fingerprint-2" {...props}></Icon>
