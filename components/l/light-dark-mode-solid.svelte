<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs8b_jbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs8b_jbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:light-dark-mode-solid" {...props}></Icon>
