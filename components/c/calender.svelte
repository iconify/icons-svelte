<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k38g4obld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k38g4obld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:calender" {...props}></Icon>
