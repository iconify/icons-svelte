<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvlhzvb1u.css';
import '../../css/n/ngozc736n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hvlhzvb1u"/><path clip-rule="evenodd" class="ngozc736n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bag-minus-solid" {...props}></Icon>
