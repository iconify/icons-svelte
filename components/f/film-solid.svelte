<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7oil4my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx7oil4my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:film-solid" {...props}></Icon>
