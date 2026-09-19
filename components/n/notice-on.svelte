<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ege3f6bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ege3f6bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:notice-on" {...props}></Icon>
