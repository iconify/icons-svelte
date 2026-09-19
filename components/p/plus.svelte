<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ri24b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i2ri24b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:plus" {...props}></Icon>
