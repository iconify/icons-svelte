<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd5kt62js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd5kt62js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rainmeter" {...props}></Icon>
