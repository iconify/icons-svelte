<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/her-4fbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="her-4fbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:list-ul" {...props}></Icon>
