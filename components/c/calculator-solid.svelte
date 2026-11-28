<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bygxr9bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bygxr9bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calculator-solid" {...props}></Icon>
