<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmgrhxbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmgrhxbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-thumb-up-solid" {...props}></Icon>
