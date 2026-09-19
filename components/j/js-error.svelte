<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzl8onbyv.css';
import '../../css/a/af2-mdbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fzl8onbyv"/><path class="af2-mdbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:js-error" {...props}></Icon>
