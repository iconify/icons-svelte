<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh0186bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh0186bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:axe-solid" {...props}></Icon>
