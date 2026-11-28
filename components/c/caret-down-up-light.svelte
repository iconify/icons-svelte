<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o777mrb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o777mrb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:caret-down-up-light" {...props}></Icon>
