<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb5d9ngtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="eb5d9ngtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-angry" {...props}></Icon>
