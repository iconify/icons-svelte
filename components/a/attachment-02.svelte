<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2fub7b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2fub7b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:attachment-02" {...props}></Icon>
