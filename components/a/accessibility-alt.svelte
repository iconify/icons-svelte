<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxrvpzbit.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dxrvpzbit"/><circle class="ob_nbubvj"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accessibility-alt" {...props}></Icon>
