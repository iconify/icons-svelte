<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofaq-pqxl.css';
import '../../css/p/ph8y6rbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofaq-pqxl"/><path class="ph8y6rbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-rain-fill" {...props}></Icon>
