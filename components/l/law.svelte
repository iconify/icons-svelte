<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eay-1bttg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eay-1bttg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:law" {...props}></Icon>
