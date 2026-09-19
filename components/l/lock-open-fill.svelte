<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di1z4achv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="di1z4achv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lock-open-fill" {...props}></Icon>
