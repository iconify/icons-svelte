<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abki_wbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="abki_wbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:double-arrow-down" {...props}></Icon>
