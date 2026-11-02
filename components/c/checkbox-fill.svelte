<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb7zffl6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb7zffl6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:checkbox-fill" {...props}></Icon>
