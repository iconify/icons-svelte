<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn29a_4bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hn29a_4bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:link-remove-solid" {...props}></Icon>
