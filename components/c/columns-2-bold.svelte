<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaw7fzylm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaw7fzylm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-2-bold" {...props}></Icon>
