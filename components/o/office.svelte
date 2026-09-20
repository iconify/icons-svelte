<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdams4bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kdams4bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:office" {...props}></Icon>
