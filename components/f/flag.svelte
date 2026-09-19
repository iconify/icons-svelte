<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qblge1bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qblge1bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:flag" {...props}></Icon>
