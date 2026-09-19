<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7arko27i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j7arko27i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:pin-slash-fill" {...props}></Icon>
