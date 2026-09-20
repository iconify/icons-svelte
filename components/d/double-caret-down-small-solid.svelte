<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo-1i0jab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="yo-1i0jab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-down-small-solid" {...props}></Icon>
