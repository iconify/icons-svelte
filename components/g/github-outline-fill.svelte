<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxm-s4boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxm-s4boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:github-outline-fill" {...props}></Icon>
