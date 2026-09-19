<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig7-kti0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ig7-kti0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:question-mark-circle-solid" {...props}></Icon>
