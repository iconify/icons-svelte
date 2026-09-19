<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc9l-bcsn.css';
import '../../css/b/b16rfrbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qc9l-bcsn"/><path class="b16rfrbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:package" {...props}></Icon>
