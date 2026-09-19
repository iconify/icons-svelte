<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpr5uwbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpr5uwbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-left-01" {...props}></Icon>
