<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc3rm6i6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc3rm6i6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:layout-minus" {...props}></Icon>
