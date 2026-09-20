<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwcieybdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwcieybdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:deepseek-line" {...props}></Icon>
