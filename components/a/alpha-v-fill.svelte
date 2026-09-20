<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owl0vibvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="owl0vibvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-v-fill" {...props}></Icon>
