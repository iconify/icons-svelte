<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9h5ad7cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9h5ad7cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-8-box-multiple" {...props}></Icon>
