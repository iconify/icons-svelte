<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvqpby2ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvqpby2ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-settings-corner-fill-round" {...props}></Icon>
