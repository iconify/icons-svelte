<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyvcic_1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvcic_1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:log-out-solid" {...props}></Icon>
