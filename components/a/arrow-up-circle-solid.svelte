<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apo15lbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="apo15lbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-up-circle-solid" {...props}></Icon>
