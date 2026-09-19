<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efl6eqbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="efl6eqbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:anchor" {...props}></Icon>
