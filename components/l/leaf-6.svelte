<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o48combuk.css';
import '../../css/m/m0bye0bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="o48combuk"/><path class="m0bye0bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:leaf-6" {...props}></Icon>
