<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcleg0b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tcleg0b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-check-20-solid" {...props}></Icon>
