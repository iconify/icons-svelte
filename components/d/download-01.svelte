<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anpr5tboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anpr5tboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:download-01" {...props}></Icon>
