<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuqqggich.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqqggich"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-square" {...props}></Icon>
