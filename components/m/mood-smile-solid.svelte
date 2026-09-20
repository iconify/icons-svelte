<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2crrsbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="o2crrsbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-smile-solid" {...props}></Icon>
