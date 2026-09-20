<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml0qwybrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ml0qwybrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-minus-solid" {...props}></Icon>
