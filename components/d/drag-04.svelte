<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui_kecyqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui_kecyqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:drag-04" {...props}></Icon>
