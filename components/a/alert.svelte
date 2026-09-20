<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu47f4b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iu47f4b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:alert" {...props}></Icon>
