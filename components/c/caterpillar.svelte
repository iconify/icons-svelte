<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwvig6vbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwvig6vbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:caterpillar" {...props}></Icon>
