<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7y_evbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o7y_evbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:i-d-badge" {...props}></Icon>
