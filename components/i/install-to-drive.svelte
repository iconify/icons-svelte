<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kugk6f76b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kugk6f76b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:install-to-drive" {...props}></Icon>
