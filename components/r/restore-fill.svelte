<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_n4uc-vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_n4uc-vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:restore-fill" {...props}></Icon>
