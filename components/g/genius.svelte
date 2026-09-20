<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu7v-1qzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu7v-1qzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:genius" {...props}></Icon>
