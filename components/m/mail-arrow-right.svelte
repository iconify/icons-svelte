<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvdgx_4vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvdgx_4vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-arrow-right" {...props}></Icon>
