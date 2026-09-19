<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oopo85q-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="oopo85q-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-left-square-fill" {...props}></Icon>
