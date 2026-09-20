<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehxg8b96x.css';
import '../../css/y/yhh61y7yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ehxg8b96x"/><path clip-rule="evenodd" class="yhh61y7yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:angular-solid" {...props}></Icon>
