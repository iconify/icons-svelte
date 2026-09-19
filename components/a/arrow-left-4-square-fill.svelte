<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_mdh6bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_mdh6bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-4-square-fill" {...props}></Icon>
