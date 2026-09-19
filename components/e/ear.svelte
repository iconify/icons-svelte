<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn1mi4dfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jn1mi4dfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:ear" {...props}></Icon>
