<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehpzqbbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehpzqbbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-linear" {...props}></Icon>
