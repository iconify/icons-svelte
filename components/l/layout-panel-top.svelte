<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3jqvu3ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3jqvu3ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layout-panel-top" {...props}></Icon>
