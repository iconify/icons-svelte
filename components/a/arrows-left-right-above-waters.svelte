<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzdi1u2bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bzdi1u2bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-left-right-above-waters" {...props}></Icon>
