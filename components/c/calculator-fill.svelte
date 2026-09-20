<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmbk-01jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbk-01jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calculator-fill" {...props}></Icon>
