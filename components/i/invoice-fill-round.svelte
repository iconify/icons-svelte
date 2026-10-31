<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui_kllv4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui_kllv4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:invoice-fill-round" {...props}></Icon>
