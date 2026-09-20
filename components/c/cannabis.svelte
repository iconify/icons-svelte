<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyfzdl32f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyfzdl32f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cannabis" {...props}></Icon>
