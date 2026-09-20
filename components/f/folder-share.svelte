<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amr6prbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amr6prbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-share" {...props}></Icon>
