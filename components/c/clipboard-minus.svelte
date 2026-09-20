<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw6nctb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw6nctb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-minus" {...props}></Icon>
