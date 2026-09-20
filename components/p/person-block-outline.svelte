<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyb3f2buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyb3f2buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-block-outline" {...props}></Icon>
