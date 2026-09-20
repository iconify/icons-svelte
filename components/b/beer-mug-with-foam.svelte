<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8iyr9bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n8iyr9bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:beer-mug-with-foam" {...props}></Icon>
