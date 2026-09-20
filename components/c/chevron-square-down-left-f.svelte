<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2bzfmb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="o2bzfmb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-square-down-left-f" {...props}></Icon>
