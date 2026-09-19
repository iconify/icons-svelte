<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noz_5wbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="noz_5wbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-doc-fill" {...props}></Icon>
