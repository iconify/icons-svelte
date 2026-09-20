<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hef1qdbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hef1qdbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:down-circle-solid" {...props}></Icon>
