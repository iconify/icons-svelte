<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz36_hsut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hz36_hsut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid" {...props}></Icon>
