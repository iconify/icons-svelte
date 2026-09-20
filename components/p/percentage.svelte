<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krs-b1nao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krs-b1nao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:percentage" {...props}></Icon>
