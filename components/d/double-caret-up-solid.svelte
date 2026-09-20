<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdgye8b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kdgye8b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-up-solid" {...props}></Icon>
