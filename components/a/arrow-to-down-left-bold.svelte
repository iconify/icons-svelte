<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgvnwj71y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qgvnwj71y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-left-bold" {...props}></Icon>
