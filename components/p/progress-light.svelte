<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyj4jwbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyj4jwbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:progress-light" {...props}></Icon>
