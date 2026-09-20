<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t16b_2bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t16b_2bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-kanban" {...props}></Icon>
