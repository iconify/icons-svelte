<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fplc9dbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fplc9dbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dots" {...props}></Icon>
