<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuz27zgrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuz27zgrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-align-left-fill" {...props}></Icon>
