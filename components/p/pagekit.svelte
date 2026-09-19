<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iczqnlbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iczqnlbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:pagekit" {...props}></Icon>
