<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqg48nbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tqg48nbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clock-solid" {...props}></Icon>
