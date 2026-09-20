<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5urk7xor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5urk7xor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flyway" {...props}></Icon>
