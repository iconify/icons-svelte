<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q919pubya.css';
import '../../css/e/epbp3tnvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="q919pubya"/><path class="epbp3tnvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pin-fill" {...props}></Icon>
