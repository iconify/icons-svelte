<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyjig5boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="oyjig5boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down" {...props}></Icon>
