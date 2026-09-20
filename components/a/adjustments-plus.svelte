<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlsj3jbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlsj3jbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-plus" {...props}></Icon>
