<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvjsmgb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvjsmgb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-diagonal-left" {...props}></Icon>
