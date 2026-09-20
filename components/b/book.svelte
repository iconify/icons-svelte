<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cetpj1bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cetpj1bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:book" {...props}></Icon>
