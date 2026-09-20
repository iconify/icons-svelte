<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td1zipb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="td1zipb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-difference-solid" {...props}></Icon>
